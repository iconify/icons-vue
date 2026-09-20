<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv1e92boa.css';
import '../../css/r/rtvgfzeze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv1e92boa"/><path class="rtvgfzeze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:route" /></template>
