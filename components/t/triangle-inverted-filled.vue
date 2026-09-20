<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a68djfbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a68djfbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:triangle-inverted-filled" /></template>
