<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_jiwnb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c_jiwnb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rand-solid" /></template>
