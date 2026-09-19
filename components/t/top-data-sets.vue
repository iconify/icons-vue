<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmtb2gbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tmtb2gbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:top-data-sets" /></template>
