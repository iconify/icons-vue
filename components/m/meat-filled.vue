<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thp3xzwhd.css';
import '../../css/e/ez9lk7bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thp3xzwhd"/><path class="ez9lk7bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:meat-filled" /></template>
