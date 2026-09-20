<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6n_93bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6n_93bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:transfer-long-right-light" /></template>
