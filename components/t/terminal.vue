<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c65rc4bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c65rc4bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:terminal" /></template>
