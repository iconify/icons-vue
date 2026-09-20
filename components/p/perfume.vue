<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhdeawf9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhdeawf9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:perfume" /></template>
