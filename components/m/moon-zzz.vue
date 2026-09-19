<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db7jd3bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="db7jd3bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:moon-zzz" /></template>
