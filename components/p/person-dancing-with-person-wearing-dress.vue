<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_utkbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ca_utkbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-dancing-with-person-wearing-dress" /></template>
