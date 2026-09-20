<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfl1ecc1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfl1ecc1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:yandex-cloud" /></template>
