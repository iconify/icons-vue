<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsh-ubcwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsh-ubcwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:megaphone" /></template>
