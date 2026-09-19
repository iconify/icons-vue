<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6embgs7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6embgs7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:underpants-02" /></template>
