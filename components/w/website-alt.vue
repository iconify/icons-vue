<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh0unhbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jh0unhbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:website-alt" /></template>
