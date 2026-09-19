<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phhyu2bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="phhyu2bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:protractor-wordmark" /></template>
