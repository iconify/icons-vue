<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr0g9xbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fr0g9xbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:translate" /></template>
