<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de261jbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:womenswear-department" /></template>
<style>
.de261jbny {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.19 8.25l-.443-5.312q-.006-.074-.026-.145t-.054-.137t-.08-.123t-.103-.106q-.056-.047-.121-.083q-.064-.036-.135-.058q-.07-.023-.143-.031q-.074-.009-.147-.002q-.149.012-.282.08q-.132.069-.229.183q-.096.113-.141.256q-.046.142-.033.29l.487 5.847l-3.952 11.854q-.047.141-.036.29q.01.149.077.282q.067.134.18.232q.112.097.254.145q.115.038.237.038h13q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.122-.038-.237L15.26 8.909l.487-5.847q.013-.148-.033-.29q-.045-.143-.141-.256q-.097-.114-.229-.183q-.133-.068-.282-.08q-.073-.007-.147.002q-.073.008-.143.031q-.071.022-.135.058t-.121.083t-.103.106t-.08.123q-.034.066-.054.137t-.026.145L13.81 8.25zm-.149 1.5h3.918l3.5 10.5H6.541z");
}

</style>
