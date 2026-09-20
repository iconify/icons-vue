<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stpj4mbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stpj4mbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-one-or-many-to-zero-or-many" /></template>
