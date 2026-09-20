<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nii0p1blk.css';
import '../../css/h/h631kg9bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nii0p1blk"/><circle class="h631kg9bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:status" /></template>
