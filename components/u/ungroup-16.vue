<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnovpgzed.css';
import '../../css/j/jikoplbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tnovpgzed"/><path clip-rule="evenodd" class="jikoplbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:ungroup-16" /></template>
