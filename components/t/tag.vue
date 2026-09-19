<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paef-ikde.css';
import '../../css/o/o04e0f4tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="paef-ikde"/><circle class="o04e0f4tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:tag" /></template>
