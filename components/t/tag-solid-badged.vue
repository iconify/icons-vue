<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd5fshb7k.css';
import '../../css/v/v1a-uw1og.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged zd5fshb7k"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-2--badged v1a-uw1og"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tag-solid-badged" /></template>
