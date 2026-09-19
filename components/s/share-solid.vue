<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8w08ccil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8w08ccil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:share-solid" /></template>
