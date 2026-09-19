<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om-kxybtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="om-kxybtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:share-ios" /></template>
