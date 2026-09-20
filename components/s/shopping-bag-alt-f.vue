<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj1nqubkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="sj1nqubkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:shopping-bag-alt-f" /></template>
