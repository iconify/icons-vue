<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f98pwhmyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f98pwhmyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:mobile-phone-solid" /></template>
