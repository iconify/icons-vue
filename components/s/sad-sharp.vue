<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io94jmbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="io94jmbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:sad-sharp" /></template>
