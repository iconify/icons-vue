<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_fshnb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_fshnb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:multiple-forward-right-outline" /></template>
