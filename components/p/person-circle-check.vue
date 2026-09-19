<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjn0y42br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kjn0y42br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-circle-check" /></template>
