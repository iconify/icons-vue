<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8ofd0bhe.css';
import '../../css/m/m4slzdbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8ofd0bhe"/><path class="m4slzdbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-outgoing-fill" /></template>
