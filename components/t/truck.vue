<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec7mc1bpe.css';
import '../../css/g/g6kyzbcgj.css';
import '../../css/k/kymmh3mru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ec7mc1bpe"/><path class="g6kyzbcgj"/><path class="kymmh3mru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:truck" /></template>
