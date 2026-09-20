<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4wx3obrc.css';
import '../../css/g/gh150gboq.css';
import '../../css/h/hvxlkhblw.css';
import '../../css/a/apbf24dvd.css';
import '../../css/k/kq2tyibcm.css';
import '../../css/s/snp287xku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c4wx3obrc"/><path class="gh150gboq"/><path class="hvxlkhblw"/><path class="apbf24dvd"/><path class="kq2tyibcm"/><path class="snp287xku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:north-korea" /></template>
