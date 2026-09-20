<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgspm5e_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hgspm5e_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mailchimp" /></template>
