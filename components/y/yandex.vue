<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk-idjbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":580.641,"height":1000};
const content = `<path class="lk-idjbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:yandex" /></template>
