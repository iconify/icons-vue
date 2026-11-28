<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3sibft6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3sibft6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phone-forwarded-solid" /></template>
