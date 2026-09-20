<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt0me_b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qt0me_b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sign-hashtag-remix" /></template>
