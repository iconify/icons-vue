<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnmpcutlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="nnmpcutlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:phabricator" /></template>
