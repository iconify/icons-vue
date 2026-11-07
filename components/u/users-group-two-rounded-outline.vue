<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6d250bwp.css';
import '../../css/e/e6101wj0a.css';
import '../../css/h/hlvhjsz4e.css';
import '../../css/d/dg1k72fde.css';
import '../../css/s/se0dh3dto.css';
import '../../css/z/zno4v69ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6d250bwp"/><path class="e6101wj0a"/><path class="hlvhjsz4e"/><path clip-rule="evenodd" class="dg1k72fde"/><path class="se0dh3dto"/><path class="zno4v69ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:users-group-two-rounded-outline" /></template>
