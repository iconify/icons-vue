<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edhclhbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edhclhbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:volume" /></template>
