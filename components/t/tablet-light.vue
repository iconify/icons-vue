<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0hp6jb5d.css';
import '../../css/h/hzx-5b09c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0hp6jb5d"/><path class="hzx-5b09c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:tablet-light" /></template>
