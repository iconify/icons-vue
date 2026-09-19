<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld-pkh_3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-pkh_3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:share-android" /></template>
