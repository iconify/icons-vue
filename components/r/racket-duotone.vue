<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2ybdh-6b.css';
import '../../css/u/utixu3psl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ybdh-6b"/><path class="utixu3psl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:racket-duotone" /></template>
