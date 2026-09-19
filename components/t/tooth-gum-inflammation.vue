<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1mwf5jar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1mwf5jar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-gum-inflammation" /></template>
