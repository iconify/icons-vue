<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nickjxuqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nickjxuqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-mail-dark" /></template>
