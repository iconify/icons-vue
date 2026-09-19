<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghc3qljav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ghc3qljav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:widget-26" /></template>
