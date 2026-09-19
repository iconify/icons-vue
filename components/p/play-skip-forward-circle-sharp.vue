<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnoh7r61d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnoh7r61d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-skip-forward-circle-sharp" /></template>
