<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqx4czu-u.css';
import '../../css/k/koinx6osy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqx4czu-u"/><path class="koinx6osy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:organization-24" /></template>
