<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3nuv0byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c3nuv0byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sound-on-solid" /></template>
