<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw63te55b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xw63te55b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:woodpecker-ci-dark" /></template>
