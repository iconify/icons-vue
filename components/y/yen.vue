<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8d05wtmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="k8d05wtmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:yen" /></template>
