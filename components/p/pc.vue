<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-7h8fb2z.css';
import '../../css/r/r21n4gx1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-7h8fb2z"/><path class="r21n4gx1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pc" /></template>
