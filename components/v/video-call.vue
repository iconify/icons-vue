<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plbs_mblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="plbs_mblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:video-call" /></template>
