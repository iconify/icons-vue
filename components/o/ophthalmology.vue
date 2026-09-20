<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxmhkjbxg.css';
import '../../css/c/cv78y-btj.css';
import '../../css/z/z9rvppbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zxmhkjbxg"/><path class="cv78y-btj"/><path class="z9rvppbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:ophthalmology" /></template>
