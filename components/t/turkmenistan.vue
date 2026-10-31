<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avaz35vcl.css';
import '../../css/d/d6irxobcr.css';
import '../../css/s/s9f_vlb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="avaz35vcl"/><path class="d6irxobcr"/><path class="s9f_vlb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:turkmenistan" /></template>
