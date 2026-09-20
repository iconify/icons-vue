<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5dal4qlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5dal4qlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:note-text-fill" /></template>
