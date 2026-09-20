<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2qjmfbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reset-shutter-speed-rounded" /></template>
<style>
.b2qjmfbcj {
  fill: currentColor;
  d: path("M11.98 16.52q0-1.01.415-1.884q.415-.872 1.113-1.495l1.938 3.378zm2.27 3.876q-.829-.467-1.406-1.23q-.577-.764-.782-1.743h3.902zm1.714-4.78l-1.714-2.993q.517-.286 1.075-.455T16.5 12q.367 0 .716.066q.35.065.686.19zm.536 5.403q-.367 0-.726-.065q-.358-.066-.695-.19l1.938-3.341l1.733 2.973q-.517.287-1.075.455t-1.175.168m.517-5.403l1.733-2.993q.829.468 1.396 1.24q.568.774.773 1.753zm2.456 4.263l-1.939-3.36H21q0 1.01-.412 1.873t-1.115 1.487M12 5Q9.075 5 7.038 7.038T5 12q0 2.108 1.11 3.79Q7.222 17.474 9 18.309V15.5q0-.213.143-.357T9.5 15t.357.143t.143.357v3.692q0 .349-.23.578t-.578.23H5.5q-.213 0-.357-.143T5 19.5t.143-.357T5.5 19h2.812q-1.916-1-3.114-2.851T4 12q0-1.664.626-3.118T6.34 6.34t2.542-1.714T12 4q2.562 0 4.562 1.418t2.884 3.688q.073.188 0 .38q-.073.193-.261.266q-.189.073-.384-.01t-.268-.27q-.756-1.97-2.513-3.221T12 5");
}

</style>
