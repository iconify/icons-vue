<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqvl9bh_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dqvl9bh_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:woof" /></template>
