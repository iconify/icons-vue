<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asegpn4nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="asegpn4nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-five-one-one" /></template>
