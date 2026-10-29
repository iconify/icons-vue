<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4gg4hqmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4gg4hqmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:signpost" /></template>
