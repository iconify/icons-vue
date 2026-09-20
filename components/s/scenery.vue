<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4f2u68gr.css';
import '../../css/m/m0c4jrb5p.css';
import '../../css/v/v4bnoj-6z.css';
import '../../css/i/iturx2siu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4f2u68gr"/><path class="m0c4jrb5p"/><path class="v4bnoj-6z"/><path class="iturx2siu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:scenery" /></template>
