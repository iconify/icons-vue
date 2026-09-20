<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au1cl9ewo.css';
import '../../css/j/j6u-38b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au1cl9ewo"/><path class="j6u-38b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:skype-alt" /></template>
