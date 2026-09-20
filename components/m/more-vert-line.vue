<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv62hbcmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv62hbcmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-vert-line" /></template>
