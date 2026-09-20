<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as2oyjb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as2oyjb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse" /></template>
