<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-tqdrbyb.css';
import '../../css/j/j-tmtc6ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-tqdrbyb"/><path clip-rule="evenodd" class="j-tmtc6ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-bold-duotone" /></template>
