<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbw7jyfci.css';
import '../../css/e/ebwjynfzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbw7jyfci"/><path class="ebwjynfzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:newspaper" /></template>
