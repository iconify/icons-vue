<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi0b81b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hi0b81b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-off-filled" /></template>
