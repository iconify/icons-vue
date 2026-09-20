<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns6ezvugm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:temple-hindu-rounded" /></template>
<style>
.ns6ezvugm {
  fill: currentColor;
  d: path("m8.185 7.5l1.29-4.298V2q0-.213.143-.357t.357-.143t.357.143t.143.357v1.5H13.5V2q0-.213.143-.357T14 1.5t.357.143T14.5 2v1.077L15.816 7.5zM2.5 20.5V12q0-.213.143-.357T3 11.5t.357.143T3.5 12v1.5h2.866l.307-1h10.654l.308 1H20.5V12q0-.213.143-.357T21 11.5t.357.143t.143.357v8.5q0 .402-.299.701t-.701.299h-6.192q-.349 0-.578-.23t-.23-.578V18q0-.617-.441-1.059Q12.617 16.5 12 16.5t-1.059.441T10.5 18v2.692q0 .349-.23.578t-.578.23H3.5q-.402 0-.701-.299T2.5 20.5m4.485-9l.888-3h8.254l.889 3z");
}

</style>
