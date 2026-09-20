<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-f790brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:supervisor-account-rounded" /></template>
<style>
.c-f790brl {
  fill: currentColor;
  d: path("M15.475 13.025q-.59-.59-.59-1.41q0-.819.59-1.41q.59-.59 1.41-.59q.819 0 1.41.59q.59.591.59 1.41q0 .82-.59 1.41q-.591.59-1.41.59q-.82 0-1.41-.59m-2.283 5.59q-.348 0-.577-.23q-.23-.23-.23-.577v-.093q0-.465.235-.843q.236-.378.657-.545q.862-.356 1.766-.534q.905-.178 1.842-.178q.936 0 1.841.178t1.766.534q.422.167.657.545t.236.844v.092q0 .348-.23.577q-.23.23-.578.23zm-5.7-8.107q-.876-.877-.876-2.123t.876-2.124t2.124-.877t2.123.877t.877 2.123q0 1.247-.877 2.124t-2.123.877t-2.124-.877m-4.876 6.461q0-.658.357-1.197q.358-.54.973-.799q1.327-.673 2.757-1.015q1.43-.343 2.913-.343q.548 0 1.096.054t1.096.139l-.912.892q-.548.606-.914 1.342t-.366 1.554v.225q0 .223.074.428t.227.367H3.654q-.44 0-.74-.3q-.298-.299-.298-.739z");
}

</style>
