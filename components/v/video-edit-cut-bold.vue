<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq_pzdluz.css';
import '../../css/s/sp9gcvbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq_pzdluz"/><path class="sp9gcvbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:video-edit-cut-bold" /></template>
