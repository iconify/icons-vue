<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c18qw3bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c18qw3bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:meet-and-greet-filled" /></template>
