<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b75kccc0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b75kccc0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sound-off-solid" /></template>
