<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r47indbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r47indbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:users-group" /></template>
