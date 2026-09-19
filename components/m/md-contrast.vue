<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmz_rrbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hmz_rrbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-contrast" /></template>
