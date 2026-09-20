<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssj6w-3vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssj6w-3vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:sensitive-solid" /></template>
