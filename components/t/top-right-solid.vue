<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh8cl0c0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jh8cl0c0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:top-right-solid" /></template>
