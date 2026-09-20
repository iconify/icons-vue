<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8d079btr.css';
import '../../css/r/rxqvapbkk.css';
import '../../css/t/t399ikbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z8d079btr"/><path class="rxqvapbkk"/><path class="t399ikbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rust-solid" /></template>
