<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk6lyrbfc.css';
import '../../css/l/lpm14mvjr.css';
import '../../css/s/shxtxmbiv.css';
import '../../css/r/rcxz1fmas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="uk6lyrbfc"/><path class="lpm14mvjr"/><path class="shxtxmbiv"/><path class="rcxz1fmas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:reminder-ribbon" /></template>
