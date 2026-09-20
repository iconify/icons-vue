<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o030v6xup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o030v6xup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:user-plus-fill" /></template>
