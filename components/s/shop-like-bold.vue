<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkacgwkry.css';
import '../../css/g/gilleue9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkacgwkry"/><path class="gilleue9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shop-like-bold" /></template>
