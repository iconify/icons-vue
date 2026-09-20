<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grs06_b9k.css';
import '../../css/z/zvpwxgbul.css';
import '../../css/a/aq8pp-buc.css';
import '../../css/b/b925a0-jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grs06_b9k"/><path class="zvpwxgbul"/><path class="aq8pp-buc"/><path class="b925a0-jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:volkswagen" /></template>
