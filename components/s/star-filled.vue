<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuieg7bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuieg7bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:star-filled" /></template>
