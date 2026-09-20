<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpa_lkb0t.css';
import '../../css/z/zdz2_wbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpa_lkb0t"/><path class="zdz2_wbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:people-group-light" /></template>
