<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9auz09yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9auz09yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:waterfall-up-02" /></template>
