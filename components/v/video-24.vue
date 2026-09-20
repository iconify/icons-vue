<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cle0u0bwz.css';
import '../../css/h/hb_oaob_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cle0u0bwz"/><path class="hb_oaob_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:video-24" /></template>
