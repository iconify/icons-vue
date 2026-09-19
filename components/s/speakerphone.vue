<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6v5jeb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t6v5jeb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:speakerphone" /></template>
