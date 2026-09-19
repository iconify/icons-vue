<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5rchq8iq.css';
import '../../css/j/j5gksabhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5rchq8iq"/><path class="j5gksabhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:phone-ring-filled" /></template>
