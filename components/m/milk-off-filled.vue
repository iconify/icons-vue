<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-wy2pb_f.css';
import '../../css/b/bh7vv0tuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-wy2pb_f"/><path class="bh7vv0tuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:milk-off-filled" /></template>
