<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gren7lhvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gren7lhvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:paperplane-light" /></template>
