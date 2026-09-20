<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt0wpkbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt0wpkbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wix" /></template>
