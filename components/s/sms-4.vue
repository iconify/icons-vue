<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brm49pdsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="brm49pdsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms-4" /></template>
