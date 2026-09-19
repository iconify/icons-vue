<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ufam33t.css';
import '../../css/v/vo-ay7btf.css';
import '../../css/w/w5m1tlf7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b z9ufam33t"/><path class="b vo-ay7btf"/><path class="b w5m1tlf7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:zen-browser" /></template>
