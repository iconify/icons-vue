<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrgv8z2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbrgv8z2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:users2-filled" /></template>
