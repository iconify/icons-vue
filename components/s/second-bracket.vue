<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3b3ih1nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3b3ih1nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:second-bracket" /></template>
