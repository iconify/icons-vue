<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7cv9nkec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7cv9nkec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:playlist-alternate" /></template>
