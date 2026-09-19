<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn_xmxb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="kn_xmxb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:relationshape-support-26" /></template>
