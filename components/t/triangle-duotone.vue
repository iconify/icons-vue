<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbgwscfne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wbgwscfne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-duotone" /></template>
