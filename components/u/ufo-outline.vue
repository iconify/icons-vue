<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6-2od-ft.css';
import '../../css/k/kb3qv9b3z.css';
import '../../css/z/zkdww2byo.css';
import '../../css/x/xu5i9lf5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6-2od-ft"/><path class="kb3qv9b3z"/><path class="zkdww2byo"/><path class="xu5i9lf5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-outline" /></template>
