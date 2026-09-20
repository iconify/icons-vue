<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f99k2xbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f99k2xbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sitting-on-lifeguard-stand" /></template>
