<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buj5tlirg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buj5tlirg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:octave" /></template>
