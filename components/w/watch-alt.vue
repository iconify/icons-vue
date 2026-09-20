<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayakudb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayakudb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:watch-alt" /></template>
