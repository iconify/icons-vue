<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6kdklbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j6kdklbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vaultwarden-light" /></template>
