<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk4wyzbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk4wyzbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:share-outline" /></template>
