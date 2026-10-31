<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a05ihraux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a05ihraux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-round-gloss" /></template>
