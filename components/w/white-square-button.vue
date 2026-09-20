<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iknetdbmw.css';
import '../../css/u/umgeii-gz.css';
import '../../css/f/ffr77i4rv.css';
import '../../css/z/z6s47uthj.css';
import '../../css/s/scfhkubuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="iknetdbmw"/><path class="umgeii-gz"/><path class="ffr77i4rv"/><path class="z6s47uthj"/><path class="scfhkubuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-square-button" /></template>
