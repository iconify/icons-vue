<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6d250bwp.css';
import '../../css/e/ewabd3k5e.css';
import '../../css/s/s3imwknyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6d250bwp"/><path class="ewabd3k5e"/><path clip-rule="evenodd" class="s3imwknyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-cross-rounded-outline" /></template>
