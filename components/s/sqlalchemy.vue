<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5d9wu-vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5d9wu-vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sqlalchemy" /></template>
