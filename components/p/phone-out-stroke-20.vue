<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrjmnmpml.css';
import '../../css/j/juwohhbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rrjmnmpml"/><path class="juwohhbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-out-stroke-20" /></template>
