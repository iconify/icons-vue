<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_sj-dt-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_sj-dt-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-frame2" /></template>
