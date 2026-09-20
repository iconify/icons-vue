<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaw39hbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaw39hbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:social-distancing" /></template>
