<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weij14cdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="weij14cdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wazuh-dark" /></template>
