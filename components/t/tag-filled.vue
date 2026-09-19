<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf5ffrwpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf5ffrwpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:tag-filled" /></template>
