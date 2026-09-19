<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzr7y9y0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzr7y9y0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:moon-alt-filled" /></template>
